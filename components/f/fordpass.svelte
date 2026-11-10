<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfr9t6j2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfr9t6j2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:fordpass" {...props}></Icon>
