<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lh9n0ccen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lh9n0ccen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:info-circle-solid" {...props}></Icon>
