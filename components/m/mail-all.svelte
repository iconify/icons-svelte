<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzw5cbb6b.css';
import '../../css/o/o90l0ebko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="zzw5cbb6b"/><path class="o90l0ebko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:mail-all" {...props}></Icon>
