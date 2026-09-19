<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptdinhqmn.css';
import '../../css/m/m5swtfbed.css';
import '../../css/z/zyduq6bqi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ptdinhqmn"/><path class="m5swtfbed"/><path class="zyduq6bqi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-compose" {...props}></Icon>
