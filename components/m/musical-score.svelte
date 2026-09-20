<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/elac0jvzd.css';
import '../../css/p/p9v66kg_a.css';
import '../../css/a/a03h6bchc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="elac0jvzd"/><circle class="p9v66kg_a"/><circle class="a03h6bchc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:musical-score" {...props}></Icon>
