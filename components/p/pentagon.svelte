<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/las552baf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="las552baf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pentagon" {...props}></Icon>
