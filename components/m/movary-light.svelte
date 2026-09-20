<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gra2o1ood.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gra2o1ood"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:movary-light" {...props}></Icon>
