<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p5ygdbczq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p5ygdbczq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:fast-arrow-up-square-solid" {...props}></Icon>
