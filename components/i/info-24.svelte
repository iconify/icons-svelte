<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mayhhmhqy.css';
import '../../css/z/zj49idy7n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mayhhmhqy"/><path class="zj49idy7n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:info-24" {...props}></Icon>
