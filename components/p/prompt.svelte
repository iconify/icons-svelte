<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co1qorbel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co1qorbel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:prompt" {...props}></Icon>
