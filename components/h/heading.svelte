<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3747kbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3747kbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:heading" {...props}></Icon>
