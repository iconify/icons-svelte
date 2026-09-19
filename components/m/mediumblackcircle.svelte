<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qx919ebgc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="qx919ebgc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:mediumblackcircle" {...props}></Icon>
