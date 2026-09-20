<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba4iaoq0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ba4iaoq0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image-minus-outline" {...props}></Icon>
