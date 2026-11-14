<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/brefd2wyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="brefd2wyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:remove-square" {...props}></Icon>
