<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jq6avsbww.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jq6avsbww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:align-center-vertical-line" {...props}></Icon>
