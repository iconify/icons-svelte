<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hq8bjuytw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hq8bjuytw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:align-horiz-center-simple-line" {...props}></Icon>
