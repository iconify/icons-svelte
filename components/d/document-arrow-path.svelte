<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2ud6lb8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p2ud6lb8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:document-arrow-path" {...props}></Icon>
