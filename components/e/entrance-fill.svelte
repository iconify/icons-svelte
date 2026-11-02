<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nb60v9_9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nb60v9_9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:entrance-fill" {...props}></Icon>
