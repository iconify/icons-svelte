<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udrs8xbjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="udrs8xbjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:like" {...props}></Icon>
