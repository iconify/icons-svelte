<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f6s2r5bvy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f6s2r5bvy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:percent" {...props}></Icon>
