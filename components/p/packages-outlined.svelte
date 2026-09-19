<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a78ikzb1o.css';
import '../../css/z/zr6-qibes.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a78ikzb1o"/><path class="zr6-qibes"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:packages-outlined" {...props}></Icon>
