<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwtz1c_6i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="xwtz1c_6i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:ppe-gown2x-outline" {...props}></Icon>
