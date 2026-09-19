<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t837arbhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t837arbhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:channels-outline" {...props}></Icon>
