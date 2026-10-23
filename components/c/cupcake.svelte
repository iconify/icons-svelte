<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdj0hilva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdj0hilva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:cupcake" {...props}></Icon>
