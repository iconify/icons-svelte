<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxvbik02p.css';
import '../../css/m/m6b4vpcmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wxvbik02p"/><path class="m6b4vpcmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:message-heart-20-bold" {...props}></Icon>
