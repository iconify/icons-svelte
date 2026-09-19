<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/c/c0fhn_bpl.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGoP0jnebL"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="c0fhn_bpl"/></g></mask></defs><path mask="url(#SVGoP0jnebL)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:reduce" {...props}></Icon>
