<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ps9736b1g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ps9736b1g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fujitsu" {...props}></Icon>
