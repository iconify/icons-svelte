<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n11xp5baq.css';
import '../../css/a/a61ltbq0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path vector-effect="non-scaling-stroke" class="n11xp5baq"/><path class="a61ltbq0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermark" {...props}></Icon>
