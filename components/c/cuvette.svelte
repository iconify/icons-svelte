<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz_20wbpz.css';
import '../../css/f/f1hzz0jas.css';
import '../../css/r/r8r179s3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="nz_20wbpz"><path clip-rule="evenodd" class="f1hzz0jas"/><path class="r8r179s3m"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:cuvette" {...props}></Icon>
