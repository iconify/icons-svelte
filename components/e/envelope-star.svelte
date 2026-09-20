<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr62-8pji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr62-8pji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:envelope-star" {...props}></Icon>
