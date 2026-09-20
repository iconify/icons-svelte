<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/av47yrbtu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="av47yrbtu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:format-list-text" {...props}></Icon>
