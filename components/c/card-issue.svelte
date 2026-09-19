<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zvtspgmrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvtspgmrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:card-issue" {...props}></Icon>
