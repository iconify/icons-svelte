<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6dzq6bba.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6dzq6bba"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:light-bulb-light" {...props}></Icon>
