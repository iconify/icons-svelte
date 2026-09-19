<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/giubn9csq.css';
import '../../css/h/hkeq5cbxm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGU1VKibWi"><g class="ft5dv1b6b"><path class="giubn9csq"/><circle class="hkeq5cbxm"/></g></mask></defs><path mask="url(#SVGU1VKibWi)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:bird" {...props}></Icon>
