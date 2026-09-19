<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/c/cyzti895k.css';
import '../../css/c/cmbowxb1u.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoxqT4cMo"><g class="ufeehvblu"><path class="cyzti895k"/><path class="cmbowxb1u"/></g></mask></defs><path mask="url(#SVGoxqT4cMo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:paper-money" {...props}></Icon>
