<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q2p9diptm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q2p9diptm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:layout-right-2-fill" {...props}></Icon>
