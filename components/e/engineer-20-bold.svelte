<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y24w7huhx.css';
import '../../css/t/tqkbqbbzb.css';
import '../../css/g/g7s9nkxpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="y24w7huhx"/><path class="tqkbqbbzb"/><path class="g7s9nkxpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:engineer-20-bold" {...props}></Icon>
