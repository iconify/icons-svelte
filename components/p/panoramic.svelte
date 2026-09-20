<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru_8w8f1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru_8w8f1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:panoramic" {...props}></Icon>
