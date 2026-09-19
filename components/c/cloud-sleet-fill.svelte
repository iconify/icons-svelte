<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olmh7yxsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="olmh7yxsb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-sleet-fill" {...props}></Icon>
