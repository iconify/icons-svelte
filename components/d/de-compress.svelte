<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynnrn-bib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynnrn-bib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:de-compress" {...props}></Icon>
