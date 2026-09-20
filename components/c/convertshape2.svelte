<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bs2yaobzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bs2yaobzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:convertshape2" {...props}></Icon>
