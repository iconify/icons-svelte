<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qidryvbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1280};
const content = `<path class="qidryvbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:gamepad" {...props}></Icon>
