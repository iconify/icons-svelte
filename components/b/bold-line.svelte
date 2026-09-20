<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnc9n5bok.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnc9n5bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:bold-line" {...props}></Icon>
