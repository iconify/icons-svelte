<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/td58n_bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="td58n_bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:harmony-o-s-outlined" {...props}></Icon>
