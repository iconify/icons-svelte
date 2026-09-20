<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb67oubne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vb67oubne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:pause-24" {...props}></Icon>
