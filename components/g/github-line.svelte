<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/avy81kbhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="avy81kbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:github-line" {...props}></Icon>
