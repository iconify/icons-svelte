<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/atoj6abie.css';
import '../../css/y/yo0y45bgr.css';
import '../../css/v/vcmsx7koy.css';
import '../../css/g/gsi6ambhf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="atoj6abie"/><path class="yo0y45bgr"/><path class="vcmsx7koy"/><path class="gsi6ambhf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-toggle" {...props}></Icon>
