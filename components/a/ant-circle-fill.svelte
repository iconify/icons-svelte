<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kdp7gyb5x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="kdp7gyb5x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:ant-circle-fill" {...props}></Icon>
