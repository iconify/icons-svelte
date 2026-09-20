<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q-icpcc6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q-icpcc6y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:caret-left-small" {...props}></Icon>
