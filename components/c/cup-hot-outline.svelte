<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1f445bbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b1f445bbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cup-hot-outline" {...props}></Icon>
