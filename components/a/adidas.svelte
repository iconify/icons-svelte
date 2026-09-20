<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyrqv0bac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vyrqv0bac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:adidas" {...props}></Icon>
