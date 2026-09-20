<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nws4xlbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nws4xlbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-down-short-sharp-fill" {...props}></Icon>
