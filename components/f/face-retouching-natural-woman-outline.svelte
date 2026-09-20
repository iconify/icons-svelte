<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krpq4dddo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krpq4dddo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:face-retouching-natural-woman-outline" {...props}></Icon>
