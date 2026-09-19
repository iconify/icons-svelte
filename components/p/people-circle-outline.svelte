<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anms5nb2o.css';
import '../../css/e/epn6lpbho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="anms5nb2o"/><path class="epn6lpbho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:people-circle-outline" {...props}></Icon>
