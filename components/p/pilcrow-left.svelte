<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uc2o02nwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uc2o02nwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:pilcrow-left" {...props}></Icon>
