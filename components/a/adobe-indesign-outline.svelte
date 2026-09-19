<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gux5og_2t.css';
import '../../css/m/mjz1r4_dm.css';
import '../../css/d/daxtkab1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gux5og_2t"/><path class="mjz1r4_dm"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:adobe-indesign-outline" {...props}></Icon>
