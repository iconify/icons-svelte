<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubqgo3idq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubqgo3idq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:mvi" {...props}></Icon>
