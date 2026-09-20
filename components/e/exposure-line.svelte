<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngx224b7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ngx224b7r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:exposure-line" {...props}></Icon>
