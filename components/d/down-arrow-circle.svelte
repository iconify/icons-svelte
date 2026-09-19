<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x2o6bplzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x2o6bplzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:down-arrow-circle" {...props}></Icon>
