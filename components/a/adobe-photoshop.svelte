<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/m2blynbna.css';
import '../../css/m/mi19bcbyg.css';
import '../../css/a/alk5a23ps.css';
import '../../css/b/b0nbak58x.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7SD0cenO"><g class="s9cl3zbei"><path class="m2blynbna"/><path class="mi19bcbyg"/><path clip-rule="evenodd" class="alk5a23ps"/><path class="b0nbak58x"/></g></mask></defs><path mask="url(#SVG7SD0cenO)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:adobe-photoshop" {...props}></Icon>
