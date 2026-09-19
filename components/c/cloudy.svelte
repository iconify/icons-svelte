<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9wmphbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":27,"height":24};
const content = `<path class="v9wmphbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:cloudy" {...props}></Icon>
