<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztw6jsdfu.css';
import '../../css/p/po93bzbuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ztw6jsdfu"/><path class="po93bzbuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fileflows-forge-dark" {...props}></Icon>
