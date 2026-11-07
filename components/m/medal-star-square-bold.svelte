<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5xllqbwr.css';
import '../../css/z/zzstyjb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e5xllqbwr"/><path class="zzstyjb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-square-bold" {...props}></Icon>
