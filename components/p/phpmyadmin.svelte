<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0df5vbnb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="n0df5vbnb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:phpmyadmin" {...props}></Icon>
