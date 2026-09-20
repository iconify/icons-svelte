<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kun0h_bmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kun0h_bmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:filter" {...props}></Icon>
