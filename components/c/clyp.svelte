<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aggim0kia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aggim0kia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:clyp" {...props}></Icon>
