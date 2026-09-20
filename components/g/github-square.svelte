<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nts4t-bvo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nts4t-bvo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:github-square" {...props}></Icon>
