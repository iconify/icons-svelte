<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/s/sunx62j5d.css';
import '../../css/p/pohpzj7cj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJYGrYcpv"><g class="ufeehvblu"><path class="sunx62j5d"/><path class="pohpzj7cj"/></g></mask></defs><path mask="url(#SVGJYGrYcpv)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:crown" {...props}></Icon>
