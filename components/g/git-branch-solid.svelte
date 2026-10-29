<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-0yys_yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-0yys_yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:git-branch-solid" {...props}></Icon>
