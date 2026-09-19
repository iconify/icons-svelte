<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qjqfd70iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qjqfd70iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:navigation-off" {...props}></Icon>
