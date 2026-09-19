<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh5xl2syl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mh5xl2syl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:medal" {...props}></Icon>
