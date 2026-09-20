<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qaw7kx8vp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qaw7kx8vp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:layers-alt" {...props}></Icon>
