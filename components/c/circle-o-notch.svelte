<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugghz5fzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugghz5fzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:circle-o-notch" {...props}></Icon>
