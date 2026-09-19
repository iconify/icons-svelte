<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5i8bacxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i5i8bacxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:play-circle-filled" {...props}></Icon>
