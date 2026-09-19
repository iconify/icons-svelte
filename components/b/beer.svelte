<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqe-nepgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqe-nepgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:beer" {...props}></Icon>
