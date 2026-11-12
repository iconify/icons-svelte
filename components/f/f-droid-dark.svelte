<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n7261t-ji.css';
import '../../css/n/n9df26uis.css';
import '../../css/w/w96h6ywld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n7261t-ji"/><path class="n9df26uis"/><path class="w96h6ywld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:f-droid-dark" {...props}></Icon>
