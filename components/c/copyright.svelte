<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rgf3yzrlx.css';
import '../../css/q/qik6ntukn.css';
import '../../css/f/fa2bfw9ww.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHBJZ6dmx"><g class="ft5dv1b6b"><circle class="rgf3yzrlx"/><path class="qik6ntukn"/><path class="fa2bfw9ww"/></g></mask></defs><path mask="url(#SVGHBJZ6dmx)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:copyright" {...props}></Icon>
