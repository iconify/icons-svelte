<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa9lgcb4p.css';
import '../../css/f/fcr5at8ly.css';
import '../../css/x/x3438ebpm.css';
import '../../css/m/m34fd8bwt.css';
import '../../css/b/bmrsvjbrh.css';
import '../../css/k/k86u2d9jd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="oa9lgcb4p"/><path clip-rule="evenodd" class="fcr5at8ly"/><path class="x3438ebpm"/><circle class="m34fd8bwt"/><circle class="bmrsvjbrh"/><path class="k86u2d9jd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:reddit" {...props}></Icon>
