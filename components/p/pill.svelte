<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mzt2iu9dp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mzt2iu9dp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pill" {...props}></Icon>
