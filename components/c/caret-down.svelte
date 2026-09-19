<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7c6_u3ej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b7c6_u3ej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:caret-down" {...props}></Icon>
