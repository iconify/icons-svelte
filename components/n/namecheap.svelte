<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j-_otxb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j-_otxb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:namecheap" {...props}></Icon>
