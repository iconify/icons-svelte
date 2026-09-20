<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jp9l5nb1u.css';
import '../../css/v/v-lew9-av.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jp9l5nb1u"/><path class="v-lew9-av"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:jotty" {...props}></Icon>
