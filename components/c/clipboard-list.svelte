<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb00oo3bp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb00oo3bp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:clipboard-list" {...props}></Icon>
