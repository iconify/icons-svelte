<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/e/ebl78obby.css';
import '../../css/u/u0zcdxb8y.css';
import '../../css/o/odgjuccph.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjOy5gcWI"><g class="ufeehvblu"><path class="ebl78obby"/><path class="u0zcdxb8y"/><path class="odgjuccph"/></g></mask></defs><path mask="url(#SVGjOy5gcWI)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:consume" {...props}></Icon>
