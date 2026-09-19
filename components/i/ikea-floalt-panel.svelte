<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yz4dern3g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz4dern3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ikea-floalt-panel" {...props}></Icon>
