<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o33ws1aqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o33ws1aqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:link-variant" {...props}></Icon>
