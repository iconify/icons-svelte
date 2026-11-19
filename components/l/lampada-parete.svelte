<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzrj2wbfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzrj2wbfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:lampada-parete" {...props}></Icon>
