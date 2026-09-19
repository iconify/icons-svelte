<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi-8tsb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="pi-8tsb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:check-circle-fill-12" {...props}></Icon>
