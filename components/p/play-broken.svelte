<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyf1kh0fw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oyf1kh0fw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:play-broken" {...props}></Icon>
