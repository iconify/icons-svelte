<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iao0xe98k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iao0xe98k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:france3" {...props}></Icon>
