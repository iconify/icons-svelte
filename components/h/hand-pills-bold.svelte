<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrw-l5b1k.css';
import '../../css/o/osatibboq.css';
import '../../css/o/ooq4xdh-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrw-l5b1k"/><path class="osatibboq"/><path class="ooq4xdh-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:hand-pills-bold" {...props}></Icon>
