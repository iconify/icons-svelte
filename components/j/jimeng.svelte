<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p31g56bgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p31g56bgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:jimeng" {...props}></Icon>
