<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cp1i4ac4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cp1i4ac4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:fsn" {...props}></Icon>
