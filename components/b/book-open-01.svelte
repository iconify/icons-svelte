<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gawuyeboa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gawuyeboa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:book-open-01" {...props}></Icon>
