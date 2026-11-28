<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmx98wb3v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmx98wb3v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:playlist-plus" {...props}></Icon>
