<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha-tytpvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ha-tytpvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:pnpm-wordmark" {...props}></Icon>
