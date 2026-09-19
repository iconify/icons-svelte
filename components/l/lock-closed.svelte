<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pgr579nhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pgr579nhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-outline:lock-closed" {...props}></Icon>
