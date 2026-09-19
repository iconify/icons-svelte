<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bja12wbsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bja12wbsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:figma" {...props}></Icon>
