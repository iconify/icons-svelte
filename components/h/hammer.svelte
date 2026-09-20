<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbtgplpqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbtgplpqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hammer" {...props}></Icon>
