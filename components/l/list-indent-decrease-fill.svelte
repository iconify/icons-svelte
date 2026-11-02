<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vt7mvmblb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vt7mvmblb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-indent-decrease-fill" {...props}></Icon>
