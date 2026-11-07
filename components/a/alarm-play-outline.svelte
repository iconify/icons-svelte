<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1g0j0b-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e1g0j0b-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:alarm-play-outline" {...props}></Icon>
