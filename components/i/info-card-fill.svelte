<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px1i3m8dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="px1i3m8dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:info-card-fill" {...props}></Icon>
