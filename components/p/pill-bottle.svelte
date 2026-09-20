<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t5m1qigkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t5m1qigkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:pill-bottle" {...props}></Icon>
