<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq8br0b3r.css';
import '../../css/s/sqlb-4bxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bq8br0b3r"/><path class="sqlb-4bxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:file-question-20-bold" {...props}></Icon>
