<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/skuz2sbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="skuz2sbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fit-to-page-outline" {...props}></Icon>
