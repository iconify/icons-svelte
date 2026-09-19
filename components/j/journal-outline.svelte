<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyolq2bek.css';
import '../../css/c/c_71ubcpr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="vyolq2bek"/><path class="c_71ubcpr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:journal-outline" {...props}></Icon>
