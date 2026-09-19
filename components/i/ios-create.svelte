<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwypuebih.css';
import '../../css/c/cxt3jkwxn.css';
import '../../css/v/vhlyezb4x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwypuebih"/><path class="cxt3jkwxn"/><g><path class="vhlyezb4x"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-create" {...props}></Icon>
