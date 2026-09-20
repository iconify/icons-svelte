<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q10zoq2ps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q10zoq2ps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:libreoffice-impress" {...props}></Icon>
