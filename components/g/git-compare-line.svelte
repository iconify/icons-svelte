<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aiu379ggu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aiu379ggu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:git-compare-line" {...props}></Icon>
