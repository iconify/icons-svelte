<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss_8qxzuj.css';
import '../../css/o/od1iqpboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ss_8qxzuj"/><path class="od1iqpboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:outline" {...props}></Icon>
