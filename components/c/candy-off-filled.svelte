<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj2q-yklp.css';
import '../../css/v/v7flhwbqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dj2q-yklp"/><path class="v7flhwbqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:candy-off-filled" {...props}></Icon>
