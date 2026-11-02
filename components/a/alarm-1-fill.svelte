<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x42to7j3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x42to7j3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:alarm-1-fill" {...props}></Icon>
