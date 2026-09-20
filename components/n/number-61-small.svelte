<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-rirjbzq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-rirjbzq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-61-small" {...props}></Icon>
