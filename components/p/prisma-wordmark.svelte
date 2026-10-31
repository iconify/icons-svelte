<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o_-88obff.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="o_-88obff"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:prisma-wordmark" {...props}></Icon>
