<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_18fpb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":680};
const content = `<path class="v_18fpb1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:external" {...props}></Icon>
