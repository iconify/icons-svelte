<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6g6lkbjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6g6lkbjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:pond5" {...props}></Icon>
