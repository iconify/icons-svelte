<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q19e26bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q19e26bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:received" {...props}></Icon>
