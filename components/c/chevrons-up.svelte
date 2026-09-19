<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1qupzz3x.css';
import '../../css/t/tc13xdone.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v1qupzz3x"/><path class="tc13xdone"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:chevrons-up" {...props}></Icon>
