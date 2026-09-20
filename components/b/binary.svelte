<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuum-zhnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kuum-zhnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:binary" {...props}></Icon>
