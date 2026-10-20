<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ajktiebca.css';
import '../../css/y/yox6r2bku.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ajktiebca"/><path class="yox6r2bku"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:binoculars-20" {...props}></Icon>
