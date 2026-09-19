<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8dcpqbeq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8dcpqbeq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gg:arrows-expand-right" {...props}></Icon>
