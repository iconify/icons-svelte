<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi50_ecyu.css';
import '../../css/m/my8yzv9ss.css';
import '../../css/l/luip11i6o.css';
import '../../css/d/dj_15obqp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fi50_ecyu"/><path class="my8yzv9ss"/><g><path class="luip11i6o"/><path class="dj_15obqp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:android-contacts" {...props}></Icon>
