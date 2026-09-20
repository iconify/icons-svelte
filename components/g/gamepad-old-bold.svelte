<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xs51nf6pn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xs51nf6pn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:gamepad-old-bold" {...props}></Icon>
