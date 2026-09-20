<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arr7c3bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="arr7c3bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:discord-logo-1-block" {...props}></Icon>
