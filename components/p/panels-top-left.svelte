<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv3hncc0i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv3hncc0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:panels-top-left" {...props}></Icon>
