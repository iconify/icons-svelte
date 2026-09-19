<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lf6v6g3zs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lf6v6g3zs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:flag-outline" {...props}></Icon>
