<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avf981v6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avf981v6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:popsicle" {...props}></Icon>
