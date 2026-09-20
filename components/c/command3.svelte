<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_5cg6box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_5cg6box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:command3" {...props}></Icon>
