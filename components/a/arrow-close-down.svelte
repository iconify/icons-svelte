<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/l/l3xoro.css';
import '../../css/n/nazh2e.css';
import '../../css/f/ff411i.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c l3xoro"/><path class="a0m25c nazh2e"/><path class="a0m25c ff411i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-close-down" {...props}></Icon>
