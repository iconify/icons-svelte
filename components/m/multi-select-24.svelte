<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qw1f1uo6z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qw1f1uo6z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:multi-select-24" {...props}></Icon>
