<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8afr61ua.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8afr61ua"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:arrow-left-solid" {...props}></Icon>
