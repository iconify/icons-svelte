<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jchyuzm8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jchyuzm8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:factory" {...props}></Icon>
