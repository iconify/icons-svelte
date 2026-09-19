<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/e/ez7docclp.css';
import '../../css/f/fxrnyjbgc.css';
import '../../css/x/xzlilxrec.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGb4mctTCP"><g class="ufeehvblu"><path class="ez7docclp"/><path class="fxrnyjbgc"/><path class="xzlilxrec"/></g></mask></defs><path mask="url(#SVGb4mctTCP)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:mall-bag" {...props}></Icon>
