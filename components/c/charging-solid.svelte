<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un_cf_ubk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="un_cf_ubk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:charging-solid" {...props}></Icon>
