<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm5rvjqyj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bm5rvjqyj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:piano-24" {...props}></Icon>
