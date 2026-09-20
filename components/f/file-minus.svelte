<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhqz6verd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jhqz6verd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-minus" {...props}></Icon>
