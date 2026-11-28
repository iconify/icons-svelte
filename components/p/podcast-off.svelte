<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kwqi8rwxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kwqi8rwxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:podcast-off" {...props}></Icon>
