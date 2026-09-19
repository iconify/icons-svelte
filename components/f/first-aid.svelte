<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/angbsab-j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="angbsab-j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:first-aid" {...props}></Icon>
