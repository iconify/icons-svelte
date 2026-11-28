<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4ia2pgnk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4ia2pgnk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:accessibility" {...props}></Icon>
