<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgi23wtae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgi23wtae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:music" {...props}></Icon>
