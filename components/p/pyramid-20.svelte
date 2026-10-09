<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7ei9-u4f.css';
import '../../css/t/trjhecjvw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v7ei9-u4f"/><path class="trjhecjvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pyramid-20" {...props}></Icon>
