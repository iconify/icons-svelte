<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf7of2bdd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gf7of2bdd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:mouse2-fill" {...props}></Icon>
