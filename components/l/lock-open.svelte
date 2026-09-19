<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vaicczq3j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="vaicczq3j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:lock-open" {...props}></Icon>
