<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dz4hxtbcz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dz4hxtbcz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-5" {...props}></Icon>
