<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7z3p3oto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c7z3p3oto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:boulanger" {...props}></Icon>
