<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nfkf-qbwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nfkf-qbwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:git-merge-check" {...props}></Icon>
