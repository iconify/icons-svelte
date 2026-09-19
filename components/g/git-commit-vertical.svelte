<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3f71owim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3f71owim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:git-commit-vertical" {...props}></Icon>
