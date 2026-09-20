<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_g92t6bd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_g92t6bd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:list-ordered-two-tone" {...props}></Icon>
