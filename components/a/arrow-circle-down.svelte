<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp635cbba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vp635cbba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:arrow-circle-down" {...props}></Icon>
