<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvwsup27g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="qvwsup27g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:hourglass-with-flowing-sand" {...props}></Icon>
