<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgoe6vbte.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgoe6vbte"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:genderless-fill" {...props}></Icon>
