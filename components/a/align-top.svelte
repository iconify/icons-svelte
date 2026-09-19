<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/evh9_l6tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="evh9_l6tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:align-top" {...props}></Icon>
