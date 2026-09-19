<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjvborlel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjvborlel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:double-check" {...props}></Icon>
