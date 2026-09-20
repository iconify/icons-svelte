<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kss-o9_-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kss-o9_-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:kebab-horizontal-24" {...props}></Icon>
