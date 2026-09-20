<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uclis5b0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="uclis5b0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:cardiology" {...props}></Icon>
