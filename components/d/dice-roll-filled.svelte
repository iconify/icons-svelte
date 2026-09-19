<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c_4qgcb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c_4qgcb4x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dice-roll-filled" {...props}></Icon>
