<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bh203n_7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bh203n_7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:grill-spatula" {...props}></Icon>
