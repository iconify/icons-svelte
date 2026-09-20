<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p778mi78a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p778mi78a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:hourglass-expressive" {...props}></Icon>
