<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pbuw-_bre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pbuw-_bre"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:credit-card-x" {...props}></Icon>
