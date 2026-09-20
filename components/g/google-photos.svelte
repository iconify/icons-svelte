<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cv7fg-bkv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv7fg-bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:google-photos" {...props}></Icon>
