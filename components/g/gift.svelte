<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bdyj9pbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bdyj9pbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:gift" {...props}></Icon>
