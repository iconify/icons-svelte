<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/czd4skyyb.css';
import '../../css/c/cs8zgvbmz.css';
import '../../css/z/ziak3vd1i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="czd4skyyb"/><path class="cs8zgvbmz"/><path class="ziak3vd1i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:ozone-20" {...props}></Icon>
