<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1ygzubzy.css';
import '../../css/p/pjqpfrbrk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o1ygzubzy"/><path class="pjqpfrbrk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-headphones-human" {...props}></Icon>
