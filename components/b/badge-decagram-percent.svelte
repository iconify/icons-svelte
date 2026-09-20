<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tg6hbfl5t.css';
import '../../css/o/o7-xjtbae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tg6hbfl5t"/><path clip-rule="evenodd" class="o7-xjtbae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:badge-decagram-percent" {...props}></Icon>
