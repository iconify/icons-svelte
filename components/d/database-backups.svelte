<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdh1wltpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sdh1wltpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:database-backups" {...props}></Icon>
