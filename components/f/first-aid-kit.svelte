<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/astn9tk8w.css';
import '../../css/e/etwwuac6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="astn9tk8w"/><path class="etwwuac6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:first-aid-kit" {...props}></Icon>
