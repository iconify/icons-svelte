<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/koj92m8jb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="koj92m8jb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hapi" {...props}></Icon>
