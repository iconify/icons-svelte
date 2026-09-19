<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/ez330t4ze.css';
import '../../css/k/kdkps0bit.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdn7wKcOR"><g class="s9cl3zbei"><path class="ez330t4ze"/><path class="kdkps0bit"/></g></mask></defs><path mask="url(#SVGdn7wKcOR)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:converging-gateway" {...props}></Icon>
