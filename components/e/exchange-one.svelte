<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wwvp95byt.css';
import '../../css/b/bco27yqdx.css';
import '../../css/i/i0qcow7ud.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQkwBZpuH"><g class="wwvp95byt"><path class="bco27yqdx"/><path class="i0qcow7ud"/></g></mask></defs><path mask="url(#SVGQkwBZpuH)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:exchange-one" {...props}></Icon>
