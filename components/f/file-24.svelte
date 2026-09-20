<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txv6a2b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txv6a2b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:file-24" {...props}></Icon>
