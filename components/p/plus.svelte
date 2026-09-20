<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/c/celmyq.css';
import '../../css/q/qbipjn.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c celmyq"/><path class="a0m25c qbipjn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:plus" {...props}></Icon>
