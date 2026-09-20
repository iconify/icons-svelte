<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r48mq8ceo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r48mq8ceo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gnu-nano" {...props}></Icon>
