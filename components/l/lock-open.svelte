<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt2ibvuil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mt2ibvuil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:lock-open" {...props}></Icon>
