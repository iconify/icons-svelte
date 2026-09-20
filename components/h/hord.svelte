<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xejs2mb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xejs2mb2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:hord" {...props}></Icon>
