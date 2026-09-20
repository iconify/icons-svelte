<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cowjgms5u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cowjgms5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:playstation-5" {...props}></Icon>
