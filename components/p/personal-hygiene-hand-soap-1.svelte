<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ks6--tb3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ks6--tb3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="covid:personal-hygiene-hand-soap-1" {...props}></Icon>
