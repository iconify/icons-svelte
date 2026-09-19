<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ocdgddc2f.css';
import '../../css/w/wk87j1b9c.css';
import '../../css/i/itu3zmsxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ocdgddc2f"/><path clip-rule="evenodd" class="wk87j1b9c"/><path class="itu3zmsxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:map-location-outline" {...props}></Icon>
