<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vj0mo180q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vj0mo180q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:crop" {...props}></Icon>
