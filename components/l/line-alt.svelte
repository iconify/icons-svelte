<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o0c2gbcdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o0c2gbcdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:line-alt" {...props}></Icon>
