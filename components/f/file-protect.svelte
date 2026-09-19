<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj03nbfem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fj03nbfem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-protect" {...props}></Icon>
