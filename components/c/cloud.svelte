<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvo00ebqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvo00ebqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fe:cloud" {...props}></Icon>
