<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ly5v89bze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ly5v89bze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:parentheses-gloss" {...props}></Icon>
