<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1wyruk-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w1wyruk-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:angularjs" {...props}></Icon>
