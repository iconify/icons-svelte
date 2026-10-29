<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ops65ob5s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ops65ob5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:braces" {...props}></Icon>
