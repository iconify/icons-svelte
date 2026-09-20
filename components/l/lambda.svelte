<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylojk-10a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ylojk-10a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:lambda" {...props}></Icon>
