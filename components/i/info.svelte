<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/x6s3-gesu.css';
import '../../css/t/tdzw1ryds.css';
import '../../css/o/osytmmx4l.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtuRKCcwE"><g class="ft5dv1b6b"><path class="x6s3-gesu"/><path clip-rule="evenodd" class="tdzw1ryds"/><path class="osytmmx4l"/></g></mask></defs><path mask="url(#SVGtuRKCcwE)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:info" {...props}></Icon>
