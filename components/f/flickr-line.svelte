<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is7teybgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="is7teybgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flickr-line" {...props}></Icon>
