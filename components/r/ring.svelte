<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_tkv6bpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n_tkv6bpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:ring" {...props}></Icon>
