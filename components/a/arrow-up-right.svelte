<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z1byibb9b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z1byibb9b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-up-right" {...props}></Icon>
