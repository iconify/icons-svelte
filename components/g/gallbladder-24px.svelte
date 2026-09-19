<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3la963tn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3la963tn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:gallbladder-24px" {...props}></Icon>
