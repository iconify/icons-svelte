<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/nvxkylbdg.css';
import '../../css/y/yyx_3z7mv.css';
import '../../css/c/c6nrszujt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGuSC5DboZ"><g class="v3_i3wktz"><path class="nvxkylbdg"/><path clip-rule="evenodd" class="yyx_3z7mv"/><path class="c6nrszujt"/></g></mask></defs><path mask="url(#SVGuSC5DboZ)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:open-door" {...props}></Icon>
