<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxb2f-u5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="qxb2f-u5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gravity-ui:copy-arrow-right" {...props}></Icon>
