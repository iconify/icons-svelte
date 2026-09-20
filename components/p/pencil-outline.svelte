<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufnqugb_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ufnqugb_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pencil-outline" {...props}></Icon>
