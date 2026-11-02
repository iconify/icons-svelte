<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uozvk3bqe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uozvk3bqe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-pull-request-close-fill" {...props}></Icon>
