<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brx7nk65y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brx7nk65y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:food-hot-dog" {...props}></Icon>
