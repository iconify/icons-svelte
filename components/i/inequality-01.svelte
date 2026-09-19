<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nqe0ola9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nqe0ola9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:inequality-01" {...props}></Icon>
