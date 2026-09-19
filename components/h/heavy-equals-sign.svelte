<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha_ce1bjt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ha_ce1bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:heavy-equals-sign" {...props}></Icon>
