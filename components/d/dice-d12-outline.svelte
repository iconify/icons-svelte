<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh8uhlb9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh8uhlb9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dice-d12-outline" {...props}></Icon>
