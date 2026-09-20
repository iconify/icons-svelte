<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avw4glfim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="avw4glfim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:atm-text-above-banknote-in-slot" {...props}></Icon>
