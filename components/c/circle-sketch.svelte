<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o63jc9t6f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o63jc9t6f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-sketch" {...props}></Icon>
