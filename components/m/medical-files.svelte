<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/z/zo7kwhb-r.css';
import '../../css/a/avz1rybom.css';
import '../../css/e/ehh3wwbgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="zo7kwhb-r"/><path class="avz1rybom"/><path class="ehh3wwbgj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:medical-files" {...props}></Icon>
