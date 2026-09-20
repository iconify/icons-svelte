<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln60e7d1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ln60e7d1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:folder-minus" {...props}></Icon>
