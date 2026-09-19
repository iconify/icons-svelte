<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vr2o12b8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="vr2o12b8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:copies-small" {...props}></Icon>
