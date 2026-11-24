<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkeen_bhs.css';
import '../../css/v/v7kledb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkeen_bhs"/><path clip-rule="evenodd" class="v7kledb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gpu-filled" {...props}></Icon>
