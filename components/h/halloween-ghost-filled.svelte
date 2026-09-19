<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vie3v6bho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vie3v6bho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:halloween-ghost-filled" {...props}></Icon>
