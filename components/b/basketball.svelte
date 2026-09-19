<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn3ror_qv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wn3ror_qv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:basketball" {...props}></Icon>
