<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/u/ujlqtjraf.css';
import '../../css/b/b7xcik0eh.css';
import '../../css/i/i499bq7-i.css';
import '../../css/d/dyisvyq3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="ujlqtjraf"/><path class="b7xcik0eh"/><rect class="i499bq7-i"/><path class="dyisvyq3k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:bee" {...props}></Icon>
