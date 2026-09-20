<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjcbu7bud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hjcbu7bud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-circle-right-filled" {...props}></Icon>
