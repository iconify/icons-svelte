<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz7d6xiyp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz7d6xiyp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:github-2-line" {...props}></Icon>
