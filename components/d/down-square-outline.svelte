<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_2dy2okx.css';
import '../../css/g/gc8-4tb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="n_2dy2okx"/><path class="gc8-4tb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:down-square-outline" {...props}></Icon>
