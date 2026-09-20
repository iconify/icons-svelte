<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvc3yybml.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvc3yybml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:junie" {...props}></Icon>
