<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tb6zfvr1t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tb6zfvr1t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:flowchart-24" {...props}></Icon>
