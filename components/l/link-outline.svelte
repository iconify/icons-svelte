<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luwxsnbji.css';
import '../../css/p/pqfht_-da.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="luwxsnbji"/><path class="pqfht_-da"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:link-outline" {...props}></Icon>
