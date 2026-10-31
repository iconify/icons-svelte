<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/krh1u2c3e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="krh1u2c3e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folders-round" {...props}></Icon>
