<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otv5c1bim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="otv5c1bim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:git-close-pull-request-line" {...props}></Icon>
