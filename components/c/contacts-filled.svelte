<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0zxo92_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u0zxo92_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:contacts-filled" {...props}></Icon>
