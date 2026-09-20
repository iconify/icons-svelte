<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r8u_thbue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="r8u_thbue"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:emoji-fill" {...props}></Icon>
