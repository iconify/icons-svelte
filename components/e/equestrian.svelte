<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euemq852e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="euemq852e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:equestrian" {...props}></Icon>
