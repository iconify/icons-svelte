<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_rvatade.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b_rvatade"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:abstract-instance" {...props}></Icon>
