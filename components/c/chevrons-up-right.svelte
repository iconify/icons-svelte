<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf5x2bw6c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-5,"top":-5};
const content = `<path class="uf5x2bw6c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevrons-up-right" {...props}></Icon>
