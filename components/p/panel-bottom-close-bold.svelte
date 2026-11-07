<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fchi9zv9c.css';
import '../../css/k/kvxqcabet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fchi9zv9c"/><path class="kvxqcabet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-close-bold" {...props}></Icon>
