<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwackbbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bwackbbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:label-alt-multiple" {...props}></Icon>
