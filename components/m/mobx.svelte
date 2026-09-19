<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/go97lvg5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="go97lvg5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:mobx" {...props}></Icon>
