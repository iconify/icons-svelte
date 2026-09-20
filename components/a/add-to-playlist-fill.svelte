<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnoox0nod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnoox0nod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:add-to-playlist-fill" {...props}></Icon>
