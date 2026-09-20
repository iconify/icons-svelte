<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saghpkbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="saghpkbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:help-rhombus-outline" {...props}></Icon>
