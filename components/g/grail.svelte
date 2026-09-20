<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl2f5eiiz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yl2f5eiiz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:grail" {...props}></Icon>
