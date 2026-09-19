<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpl7y8bqq.css';
import '../../css/k/kebsqacsd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lpl7y8bqq"/><path class="kebsqacsd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eva:mic-off-outline" {...props}></Icon>
