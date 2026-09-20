<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0y_70meq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="n0y_70meq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-circle-down-left-f" {...props}></Icon>
