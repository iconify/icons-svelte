<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/u/uwrjvfsrp.css';
import '../../css/p/p-rbzybho.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkzVThlsm"><g class="ufeehvblu"><path class="uwrjvfsrp"/><path class="p-rbzybho"/></g></mask></defs><path mask="url(#SVGkzVThlsm)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:medicine-bottle-one" {...props}></Icon>
