<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/y/ybiggrbdo.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG2PKXdeWI"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="ybiggrbdo"/></g></mask></defs><path mask="url(#SVG2PKXdeWI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:align-text-both-one" {...props}></Icon>
