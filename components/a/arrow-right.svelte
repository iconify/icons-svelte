<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/clml3gbpq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="clml3gbpq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="nrk:arrow-right" {...props}></Icon>
