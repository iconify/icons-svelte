<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/x/xo01bq3gx.css';
import '../../css/h/hebxe4pns.css';
import '../../css/k/k2dqs591a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xo01bq3gx"/><path clip-rule="evenodd" class="hebxe4pns"/><path class="k2dqs591a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:banknotes-solid" {...props}></Icon>
