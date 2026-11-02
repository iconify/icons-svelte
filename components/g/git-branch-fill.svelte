<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8a7vcc0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w8a7vcc0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-branch-fill" {...props}></Icon>
