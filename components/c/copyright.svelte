<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-mth8bqt.css';
import '../../css/r/r7nu-ofod.css';
import '../../css/y/yk60_vm2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="g-mth8bqt"><path class="r7nu-ofod"/><path class="yk60_vm2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-flat:copyright" {...props}></Icon>
