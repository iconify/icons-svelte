<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuqh9yk4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuqh9yk4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:piggy-bank-minus" {...props}></Icon>
