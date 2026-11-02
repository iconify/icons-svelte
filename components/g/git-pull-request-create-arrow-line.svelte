<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prlh_wbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="prlh_wbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-create-arrow-line" {...props}></Icon>
