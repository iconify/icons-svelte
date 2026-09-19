<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/m/m2blynbna.css';
import '../../css/a/a_zfs7wna.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMHMLRb7Y"><g class="ufeehvblu"><path class="m2blynbna"/><path class="a_zfs7wna"/></g></mask></defs><path mask="url(#SVGMHMLRb7Y)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:align-text-left-one" {...props}></Icon>
