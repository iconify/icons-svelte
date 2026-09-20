<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdjbtzpxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdjbtzpxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:key-square-sharp-fill" {...props}></Icon>
