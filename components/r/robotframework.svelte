<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v7ksofbos.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="v7ksofbos"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:robotframework" {...props}></Icon>
