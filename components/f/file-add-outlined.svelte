<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omfz_bb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="omfz_bb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-add-outlined" {...props}></Icon>
