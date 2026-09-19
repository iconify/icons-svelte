<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lljkc8ood.css';
import '../../css/c/cn4m4xbfq.css';
import '../../css/a/a1x6v0wfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="lljkc8ood"><path class="cn4m4xbfq"/><path class="a1x6v0wfj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:empty-battery" {...props}></Icon>
