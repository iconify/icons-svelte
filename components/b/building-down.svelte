<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ut0d6c_fq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ut0d6c_fq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:building-down" {...props}></Icon>
