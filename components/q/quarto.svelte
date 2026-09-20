<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/htq3a-brb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="htq3a-brb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:quarto" {...props}></Icon>
