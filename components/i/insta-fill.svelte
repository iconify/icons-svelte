<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vla12_51k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vla12_51k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:insta-fill" {...props}></Icon>
