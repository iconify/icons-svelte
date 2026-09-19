<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iz182cbtn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iz182cbtn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:kissing-face-fill" {...props}></Icon>
