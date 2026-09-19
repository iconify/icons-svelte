<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on-1qbc1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="on-1qbc1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-plug" {...props}></Icon>
