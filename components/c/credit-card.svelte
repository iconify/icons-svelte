<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q53hz-bxg.css';
import '../../css/z/z8ovlk4ie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q53hz-bxg"/><path class="z8ovlk4ie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:credit-card" {...props}></Icon>
