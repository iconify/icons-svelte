<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f46i-9g8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f46i-9g8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:phpstan" {...props}></Icon>
