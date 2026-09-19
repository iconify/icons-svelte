<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgwrmub4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgwrmub4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:label" {...props}></Icon>
