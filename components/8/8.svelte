<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xouyc9gab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":455,"height":772};
const content = `<path class="xouyc9gab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:8" {...props}></Icon>
