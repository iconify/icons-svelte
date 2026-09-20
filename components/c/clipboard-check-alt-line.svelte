<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fr-0gy2dt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fr-0gy2dt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:clipboard-check-alt-line" {...props}></Icon>
