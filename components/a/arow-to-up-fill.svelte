<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/stse3cnyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="stse3cnyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arow-to-up-fill" {...props}></Icon>
