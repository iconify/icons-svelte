<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o1elqyk4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o1elqyk4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:indent-left" {...props}></Icon>
