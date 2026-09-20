<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcxszbbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wcxszbbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:diagram-dash-circle-large-head-bold" {...props}></Icon>
