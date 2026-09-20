<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/z/zqepbzfoi.css';
import '../../css/k/kbbyx9vwy.css';
import '../../css/q/qp8upgb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path vector-effect="non-scaling-stroke" class="zqepbzfoi"/><path vector-effect="non-scaling-stroke" class="kbbyx9vwy"/><path vector-effect="non-scaling-stroke" class="qp8upgb0h"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wordpress:comment-author-avatar" {...props}></Icon>
