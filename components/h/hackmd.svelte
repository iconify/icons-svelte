<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lx9va6bxi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lx9va6bxi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:hackmd" {...props}></Icon>
