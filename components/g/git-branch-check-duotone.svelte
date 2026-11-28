<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omjlb3bip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="omjlb3bip primary"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:git-branch-check-duotone" {...props}></Icon>
