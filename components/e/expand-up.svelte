<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/o/ojzy-1w0l.css';
import '../../css/l/lqp09mrly.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGAdmJ6bTJ"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="ojzy-1w0l"/><path class="lqp09mrly"/></g></mask></defs><path mask="url(#SVGAdmJ6bTJ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:expand-up" {...props}></Icon>
