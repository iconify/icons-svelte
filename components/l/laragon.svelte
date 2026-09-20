<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0utkdqpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0utkdqpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:laragon" {...props}></Icon>
