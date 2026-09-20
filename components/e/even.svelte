<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s03_qnhzg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="s03_qnhzg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:even" {...props}></Icon>
