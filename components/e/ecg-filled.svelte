<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kp22y890s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kp22y890s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:ecg-filled" {...props}></Icon>
