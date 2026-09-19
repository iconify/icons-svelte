<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sykatxd1a.css';
import '../../css/l/lmkh-etqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sykatxd1a"/><path class="lmkh-etqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:operations-field" {...props}></Icon>
