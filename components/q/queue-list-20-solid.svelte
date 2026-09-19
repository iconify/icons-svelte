<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ian07eb2s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ian07eb2s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:queue-list-20-solid" {...props}></Icon>
