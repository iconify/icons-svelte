<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ed37nhbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ed37nhbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:git-pull-line" {...props}></Icon>
