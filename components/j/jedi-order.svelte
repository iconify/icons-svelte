<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmw6wmnpz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="wmw6wmnpz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:jedi-order" {...props}></Icon>
