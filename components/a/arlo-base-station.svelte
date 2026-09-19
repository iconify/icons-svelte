<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l6fgimbdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6fgimbdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:arlo-base-station" {...props}></Icon>
