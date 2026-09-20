<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/st75dqbyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="st75dqbyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:airi" {...props}></Icon>
