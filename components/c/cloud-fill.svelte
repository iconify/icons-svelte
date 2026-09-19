<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2c5zztnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="i2c5zztnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-fill" {...props}></Icon>
