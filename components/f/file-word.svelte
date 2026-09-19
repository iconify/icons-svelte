<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/i/i_rbvcu_z.css';
import '../../css/k/kxz6i3bvk.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaVClCcHM"><g class="ufeehvblu"><path class="i_rbvcu_z"/><path class="kxz6i3bvk"/></g></mask></defs><path mask="url(#SVGaVClCcHM)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:file-word" {...props}></Icon>
