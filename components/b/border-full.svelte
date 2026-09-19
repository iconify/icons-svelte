<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ewuhn0xab.css';
import '../../css/t/t2g-9euft.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ewuhn0xab"/><path class="t2g-9euft"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:border-full" {...props}></Icon>
