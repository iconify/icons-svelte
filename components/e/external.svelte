<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b97j8tb8h.css';
import '../../css/c/ch0locc9x.css';
import '../../css/m/m6cgo-z4n.css';
import '../../css/b/b3y77acjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<circle class="b97j8tb8h"/><g class="ch0locc9x"><path class="m6cgo-z4n"/><path class="b3y77acjg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:external" {...props}></Icon>
