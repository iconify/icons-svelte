<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gs3ov8moq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gs3ov8moq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:margin-top" {...props}></Icon>
