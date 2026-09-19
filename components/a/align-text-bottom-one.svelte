<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/m/m799b0buj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGnvrPhbjy"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="m799b0buj"/></g></mask></defs><path mask="url(#SVGnvrPhbjy)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:align-text-bottom-one" {...props}></Icon>
