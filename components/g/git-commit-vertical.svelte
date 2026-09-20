<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na60n6bgs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na60n6bgs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-commit-vertical" {...props}></Icon>
