<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uuw37nb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uuw37nb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:ear-listen" {...props}></Icon>
