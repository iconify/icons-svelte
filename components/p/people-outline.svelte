<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d732303fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d732303fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:people-outline" {...props}></Icon>
