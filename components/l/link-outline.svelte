<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/h/hbn71sjeo.css';
import '../../css/z/zai84lbsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="link-outline"><g class="Vector n1lsf0bnc" clip-rule="evenodd"><path class="hbn71sjeo"/><path class="zai84lbsw"/></g></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cuida:link-outline" {...props}></Icon>
