<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc2s802al.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sc2s802al"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:goose-codename" {...props}></Icon>
