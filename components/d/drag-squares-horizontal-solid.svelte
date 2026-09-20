<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4h15gb0v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4h15gb0v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:drag-squares-horizontal-solid" {...props}></Icon>
