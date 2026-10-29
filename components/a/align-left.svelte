<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/deq0jmbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="deq0jmbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:align-left" {...props}></Icon>
