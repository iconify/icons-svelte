<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt2wyfadz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bt2wyfadz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:party-popper" {...props}></Icon>
