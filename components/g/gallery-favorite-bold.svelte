<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vwvsfxegk.css';
import '../../css/o/oswy_sbya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vwvsfxegk"/><path class="oswy_sbya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gallery-favorite-bold" {...props}></Icon>
