<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qbjg4bc7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qbjg4bc7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:crown-solid" {...props}></Icon>
