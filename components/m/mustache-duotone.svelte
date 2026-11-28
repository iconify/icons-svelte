<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5mruobse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a5mruobse primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mustache-duotone" {...props}></Icon>
