<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubburdbjh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ubburdbjh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:bin-1-bold" {...props}></Icon>
