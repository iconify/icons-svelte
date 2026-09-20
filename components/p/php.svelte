<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k9hy3cbqn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9hy3cbqn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:php" {...props}></Icon>
