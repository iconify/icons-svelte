<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c210f-7ji.css';
import '../../css/i/i9l7_bcpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="c210f-7ji"/><path class="i9l7_bcpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:labor-delivery" {...props}></Icon>
