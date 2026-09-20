<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-3k_lb1q.css';
import '../../css/a/a0u305bhu.css';
import '../../css/e/ewy3v6o-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-3k_lb1q"/><path class="a0u305bhu"/><path class="ewy3v6o-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:bdp" {...props}></Icon>
