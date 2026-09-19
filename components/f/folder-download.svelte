<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta4y7xbdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ta4y7xbdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:folder-download" {...props}></Icon>
