<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m4jss5ybp.css';
import '../../css/u/urj19wz9n.css';
import '../../css/k/k9zewywgp.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSQJqBKGw"><g class="s9cl3zbei"><path class="m4jss5ybp"/><path class="urj19wz9n"/><path class="k9zewywgp"/></g></mask></defs><path mask="url(#SVGSQJqBKGw)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:one-to-many" {...props}></Icon>
