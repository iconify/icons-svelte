<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m-ds1qb9a.css';
import '../../css/m/m45_auk8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m-ds1qb9a"/><path class="m45_auk8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:print-filled" {...props}></Icon>
