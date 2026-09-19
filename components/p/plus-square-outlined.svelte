<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3gr4-b7l.css';
import '../../css/g/gc8-4tb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j3gr4-b7l"/><path class="gc8-4tb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:plus-square-outlined" {...props}></Icon>
