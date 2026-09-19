<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cjdzv1dwd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":896,"height":1024};
const content = `<path class="cjdzv1dwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:kidney" {...props}></Icon>
