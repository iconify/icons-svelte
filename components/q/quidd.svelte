<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omkiu1b3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omkiu1b3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:quidd" {...props}></Icon>
