<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd_jq-bdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="zd_jq-bdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:block-1" {...props}></Icon>
