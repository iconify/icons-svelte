<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iami2m70c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="iami2m70c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:cloud-download-fill" {...props}></Icon>
