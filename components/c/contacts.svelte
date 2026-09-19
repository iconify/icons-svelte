<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ctj3b1blo.css';
import '../../css/a/a7ms1gb6t.css';
import '../../css/s/s77fccc8h.css';
import '../../css/w/wla87uw1c.css';
import '../../css/x/xad76ubit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ctj3b1blo"/><path class="a7ms1gb6t"/><g class="s77fccc8h"><circle class="wla87uw1c"/><path class="xad76ubit"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:contacts" {...props}></Icon>
