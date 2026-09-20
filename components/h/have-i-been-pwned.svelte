<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z2b7c5wsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z2b7c5wsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:have-i-been-pwned" {...props}></Icon>
