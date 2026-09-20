<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uqm1pugoc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uqm1pugoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:exercism" {...props}></Icon>
