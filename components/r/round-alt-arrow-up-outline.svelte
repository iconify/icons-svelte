<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w87kihx3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w87kihx3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:round-alt-arrow-up-outline" {...props}></Icon>
