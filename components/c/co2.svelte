<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zg0e4ebeb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zg0e4ebeb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:co2" {...props}></Icon>
