<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o3nojpbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o3nojpbsy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:circle-dashed-number-2" {...props}></Icon>
