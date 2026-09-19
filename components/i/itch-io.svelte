<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sg2o69bgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sg2o69bgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:itch-io" {...props}></Icon>
