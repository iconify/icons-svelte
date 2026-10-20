<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q9vfuu1bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q9vfuu1bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:hat-glasses" {...props}></Icon>
