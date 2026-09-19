<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_son2bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="s_son2bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:book-open" {...props}></Icon>
