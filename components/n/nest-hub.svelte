<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x84cco1-y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x84cco1-y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nest-hub" {...props}></Icon>
