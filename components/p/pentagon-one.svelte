<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uni_f1bqr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLikcWbzl"><path class="uni_f1bqr"/></mask></defs><path mask="url(#SVGLikcWbzl)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:pentagon-one" {...props}></Icon>
