<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo8h7hb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo8h7hb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:dropdown-outline" {...props}></Icon>
