<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8-hdbbsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="q8-hdbbsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-pdf-filled" {...props}></Icon>
