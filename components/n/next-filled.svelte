<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o7806flpi.css';
import '../../css/v/v9la5m20b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="o7806flpi"/><path class="v9la5m20b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:next-filled" {...props}></Icon>
