<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/y/yq0agmbxn.css';
import '../../css/q/qmr6impwm.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGE9tJNcsq"><g class="s9cl3zbei"><path class="yq0agmbxn"/><path class="qmr6impwm"/></g></mask></defs><path mask="url(#SVGE9tJNcsq)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:avocado" {...props}></Icon>
