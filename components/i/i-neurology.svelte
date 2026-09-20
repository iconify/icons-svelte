<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfvs4195e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="hfvs4195e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-neurology" {...props}></Icon>
