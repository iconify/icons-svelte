<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8umw4bej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8umw4bej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:document-duplicate" {...props}></Icon>
