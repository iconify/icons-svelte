<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/z/z4bieue7t.css';
import '../../css/n/nb4q60bwm.css';
import '../../css/d/dtbcdossj.css';
import '../../css/m/mea8r4fbu.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBHGQ4qJY"><g class="s9cl3zbei"><circle class="z4bieue7t"/><path class="nb4q60bwm"/><circle class="dtbcdossj"/><path class="mea8r4fbu"/></g></mask></defs><path mask="url(#SVGBHGQ4qJY)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:appointment" {...props}></Icon>
