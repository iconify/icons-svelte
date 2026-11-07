<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/miuz52b1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="miuz52b1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-ribbons-star-outline" {...props}></Icon>
