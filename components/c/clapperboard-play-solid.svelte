<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s33ltlbns.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s33ltlbns"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:clapperboard-play-solid" {...props}></Icon>
