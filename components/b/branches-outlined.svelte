<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xi3ewdbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xi3ewdbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:branches-outlined" {...props}></Icon>
