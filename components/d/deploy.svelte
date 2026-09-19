<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_q1xdzts.css';
import '../../css/o/ogmfbzzzw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="f_q1xdzts"/><path class="ogmfbzzzw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:deploy" {...props}></Icon>
