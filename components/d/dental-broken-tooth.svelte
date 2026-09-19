<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c6qkenbjm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c6qkenbjm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:dental-broken-tooth" {...props}></Icon>
