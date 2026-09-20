<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuw1l-bwe.css';
import '../../css/n/n1trkpqad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuw1l-bwe"/><path class="n1trkpqad"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:coding-apps-website-smartphone-protection-bold" {...props}></Icon>
