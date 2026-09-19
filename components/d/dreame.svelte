<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x6i0klbml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6i0klbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:dreame" {...props}></Icon>
