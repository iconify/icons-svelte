<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfdgfs6fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yfdgfs6fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:gatus" {...props}></Icon>
