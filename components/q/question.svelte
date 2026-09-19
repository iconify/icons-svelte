<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jig3vgbfb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":412,"height":731};
const content = `<path class="jig3vgbfb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:question" {...props}></Icon>
