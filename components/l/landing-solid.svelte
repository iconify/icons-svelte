<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q316_cceb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q316_cceb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:landing-solid" {...props}></Icon>
