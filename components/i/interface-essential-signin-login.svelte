<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eckid59_t.css';
import '../../css/t/tc-l81vik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="eckid59_t"/><path class="tc-l81vik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-signin-login" {...props}></Icon>
