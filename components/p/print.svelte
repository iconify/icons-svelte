<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cfab8ibes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cfab8ibes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:print" {...props}></Icon>
