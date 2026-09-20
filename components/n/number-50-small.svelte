<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nd6a3bk_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nd6a3bk_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:number-50-small" {...props}></Icon>
