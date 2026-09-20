<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fl69lcchu.css';
import '../../css/o/otmkmnc4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fl69lcchu"/><path class="otmkmnc4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kyoo" {...props}></Icon>
