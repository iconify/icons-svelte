<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/upq_uz6fh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="upq_uz6fh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="meteor-icons:align-justify" {...props}></Icon>
