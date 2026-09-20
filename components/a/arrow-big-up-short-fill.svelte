<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzt2xnggt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzt2xnggt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-up-short-fill" {...props}></Icon>
