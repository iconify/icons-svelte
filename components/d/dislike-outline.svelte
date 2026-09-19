<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_xwo0bva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_xwo0bva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:dislike-outline" {...props}></Icon>
