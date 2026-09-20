<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zrd9cpbdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="zrd9cpbdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:forest" {...props}></Icon>
