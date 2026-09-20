<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4xj07b2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4xj07b2p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-down-left-fill" {...props}></Icon>
