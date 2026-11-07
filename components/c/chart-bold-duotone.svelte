<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ogok9o5lk.css';
import '../../css/w/wzlj4ldvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ogok9o5lk"/><path class="wzlj4ldvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chart-bold-duotone" {...props}></Icon>
