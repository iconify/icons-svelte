<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khbe9hban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khbe9hban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:codewars" {...props}></Icon>
