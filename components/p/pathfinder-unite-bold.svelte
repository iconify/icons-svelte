<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km9qluwhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="km9qluwhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pathfinder-unite-bold" {...props}></Icon>
