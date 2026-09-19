<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu6bpab-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="fu6bpab-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:github-small" {...props}></Icon>
