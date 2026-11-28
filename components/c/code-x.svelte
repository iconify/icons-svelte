<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex4rp8bnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ex4rp8bnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:code-x" {...props}></Icon>
