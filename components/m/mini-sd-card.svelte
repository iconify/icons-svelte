<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/r/rlus9bcvf.css';
import '../../css/b/b9p_odg0a.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrCT9i6JL"><g class="s9cl3zbei"><path clip-rule="evenodd" class="rlus9bcvf"/><path class="b9p_odg0a"/></g></mask></defs><path mask="url(#SVGrCT9i6JL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:mini-sd-card" {...props}></Icon>
