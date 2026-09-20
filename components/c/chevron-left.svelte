<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nduyem.css';
import '../../css/s/so-from-12.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nduyem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-left" {...props}></Icon>
