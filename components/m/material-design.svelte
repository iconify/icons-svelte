<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iqsbbac6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="iqsbbac6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:material-design" {...props}></Icon>
