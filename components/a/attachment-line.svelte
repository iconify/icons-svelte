<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm0y7t7oq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm0y7t7oq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:attachment-line" {...props}></Icon>
