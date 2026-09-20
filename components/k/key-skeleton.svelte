<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zet4wgb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zet4wgb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:key-skeleton" {...props}></Icon>
