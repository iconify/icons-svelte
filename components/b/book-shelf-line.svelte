<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sm217z1po.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sm217z1po"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:book-shelf-line" {...props}></Icon>
