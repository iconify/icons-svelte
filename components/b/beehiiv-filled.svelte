<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab3_j_b9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ab3_j_b9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:beehiiv-filled" {...props}></Icon>
