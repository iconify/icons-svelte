<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbuxy4b5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbuxy4b5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:nanoleaf-umbra-cono" {...props}></Icon>
