<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s5awmwr5a.css';
import '../../css/n/ndq30w6of.css';
import '../../css/s/spoulug9m.css';
import '../../css/i/itm218-id.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="s5awmwr5a"/><path class="ndq30w6of"/><path class="spoulug9m"/><path class="itm218-id"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:laptop" {...props}></Icon>
