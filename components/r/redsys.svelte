<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/scimw__ky.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="scimw__ky"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:redsys" {...props}></Icon>
