<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izferu_zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":750,"height":850};
const content = `<path class="izferu_zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="il:controls" {...props}></Icon>
