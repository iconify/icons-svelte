<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d79_wtv7f.css';
import '../../css/h/hrcgbt1jd.css';
import '../../css/v/v0m5xdb6q.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<mask id="ipSEmpty0"><g class="ft5dv1b6b"><g clip-path="url(#ipSEmpty1)" class="d79_wtv7f"><path class="hrcgbt1jd"/></g><defs><clipPath id="ipSEmpty1"><path class="v0m5xdb6q"/></clipPath></defs></g></mask><path mask="url(#ipSEmpty0)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:empty" {...props}></Icon>
