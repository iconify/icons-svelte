<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q__a3ub2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q__a3ub2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:openleaf-dark" {...props}></Icon>
