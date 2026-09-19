<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s9cl3zbei.css';
import '../../css/q/qek2tkbit.css';
import '../../css/q/ql-g5bbuf.css';
import '../../css/t/tynws4brr.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxTNwcd8l"><g class="s9cl3zbei"><rect class="qek2tkbit"/><path class="ql-g5bbuf"/><path class="tynws4brr"/></g></mask></defs><path mask="url(#SVGxTNwcd8l)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:nine-key" {...props}></Icon>
