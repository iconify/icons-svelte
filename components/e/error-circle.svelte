<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ak8c2dbrq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ak8c2dbrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:error-circle" {...props}></Icon>
