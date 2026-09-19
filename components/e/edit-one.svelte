<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3lph30dl.css';
import '../../css/t/ty_00eb4z.css';
import '../../css/v/vssgzbhpi.css';
import '../../css/c/ccljrla5i.css';
import '../../css/o/otqf1nyzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="l3lph30dl"><path class="ty_00eb4z"/><path class="vssgzbhpi"/><path class="ccljrla5i"/><path class="otqf1nyzi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:edit-one" {...props}></Icon>
