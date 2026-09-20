<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4gyquu4g.css';
import '../../css/k/kuyk5mn6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="x4gyquu4g"/><path class="kuyk5mn6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:markstack-light" {...props}></Icon>
