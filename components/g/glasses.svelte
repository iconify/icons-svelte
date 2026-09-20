<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed8xp-2rp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ed8xp-2rp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:glasses" {...props}></Icon>
