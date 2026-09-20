<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_gz97l3s.css';
import '../../css/y/yn8-hpb9j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_gz97l3s"/><path class="yn8-hpb9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:rocket" {...props}></Icon>
