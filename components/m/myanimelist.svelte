<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kh2130lxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kh2130lxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:myanimelist" {...props}></Icon>
