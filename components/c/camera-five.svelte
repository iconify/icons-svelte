<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/fsrh2nb1f.css';
import '../../css/m/m8ebsac4f.css';
import '../../css/h/hyslrubfz.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCuhzJdUh"><g class="s9cl3zbei"><circle class="fsrh2nb1f"/><circle class="m8ebsac4f"/><path class="hyslrubfz"/></g></mask></defs><path mask="url(#SVGCuhzJdUh)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:camera-five" {...props}></Icon>
