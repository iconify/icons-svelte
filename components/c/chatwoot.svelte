<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/so6r9ib0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="so6r9ib0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:chatwoot" {...props}></Icon>
