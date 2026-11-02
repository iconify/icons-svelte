<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chgko6bau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chgko6bau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:maya-pyramids-fill" {...props}></Icon>
