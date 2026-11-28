<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qyxi7h06a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qyxi7h06a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:chevrons-left" {...props}></Icon>
