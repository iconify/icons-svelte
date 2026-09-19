<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dgqc87buj.css';
import '../../css/h/h7n74xhqs.css';
import '../../css/t/tcsfno7wt.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrNNsNeBC"><g class="ft5dv1b6b"><path class="dgqc87buj"/><path class="h7n74xhqs"/><path clip-rule="evenodd" class="tcsfno7wt"/></g></mask></defs><path mask="url(#SVGrNNsNeBC)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:helpcenter" {...props}></Icon>
