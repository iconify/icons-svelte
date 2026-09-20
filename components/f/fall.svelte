<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv9c24b8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pv9c24b8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:fall" {...props}></Icon>
