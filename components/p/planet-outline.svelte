<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9m8_1bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q9m8_1bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-outline" {...props}></Icon>
