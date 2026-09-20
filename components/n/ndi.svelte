<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clacabcnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clacabcnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:ndi" {...props}></Icon>
