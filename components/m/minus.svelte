<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt6v-jbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xt6v-jbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:minus" {...props}></Icon>
