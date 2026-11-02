<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovxlk2egd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovxlk2egd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-line" {...props}></Icon>
