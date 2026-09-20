<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z24sesp2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z24sesp2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:git-arrow-right-sharp" {...props}></Icon>
