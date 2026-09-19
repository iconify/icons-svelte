<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_757dk6o.css';
import '../../css/t/the1faccv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="n_757dk6o"/><path class="the1faccv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:event" {...props}></Icon>
