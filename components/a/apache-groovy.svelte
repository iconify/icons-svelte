<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oih226b6q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oih226b6q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:apache-groovy" {...props}></Icon>
