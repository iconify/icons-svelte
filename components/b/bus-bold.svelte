<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/az9avy84r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="az9avy84r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bus-bold" {...props}></Icon>
