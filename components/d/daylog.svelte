<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvvxebbmy.css';
import '../../css/x/x9osqmkwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bvvxebbmy"/><path class="x9osqmkwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:daylog" {...props}></Icon>
