<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z26as7v5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z26as7v5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:pantone-outline" {...props}></Icon>
