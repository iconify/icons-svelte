<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-99x8bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u-99x8bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:pay-circle-filled" {...props}></Icon>
