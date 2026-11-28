<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-natcc1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a-natcc1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:message-question" {...props}></Icon>
