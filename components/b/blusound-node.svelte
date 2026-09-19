<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3_4pvb5n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s3_4pvb5n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:blusound-node" {...props}></Icon>
