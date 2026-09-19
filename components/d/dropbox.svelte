<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wjbwik_ov.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":528,"height":512};
const content = `<path class="wjbwik_ov"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:dropbox" {...props}></Icon>
