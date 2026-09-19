<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-4jio4dy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o-4jio4dy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:expand-left" {...props}></Icon>
