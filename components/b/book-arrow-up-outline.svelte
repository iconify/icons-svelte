<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9fadsbgv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n9fadsbgv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-arrow-up-outline" {...props}></Icon>
