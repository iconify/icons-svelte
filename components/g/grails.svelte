<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bji6subwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bji6subwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:grails" {...props}></Icon>
