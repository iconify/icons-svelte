<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1d2lcbjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1d2lcbjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ghost-fill" {...props}></Icon>
