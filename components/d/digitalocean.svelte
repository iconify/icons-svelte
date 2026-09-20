<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl_78bb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl_78bb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:digitalocean" {...props}></Icon>
