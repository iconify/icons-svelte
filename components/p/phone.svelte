<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/qctwulbfr.css';
import '../../css/a/antt1e1xu.css';
import '../../css/o/ox3rhu33h.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGX9FZtb2j"><g class="s9cl3zbei"><path class="qctwulbfr"/><path class="antt1e1xu"/><path class="ox3rhu33h"/></g></mask></defs><path mask="url(#SVGX9FZtb2j)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:phone" {...props}></Icon>
