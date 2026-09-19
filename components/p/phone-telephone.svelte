<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eknmiedkj.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaJDgL3dK"><path class="eknmiedkj"/></mask></defs><path mask="url(#SVGaJDgL3dK)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:phone-telephone" {...props}></Icon>
