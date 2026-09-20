<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/d/dza1eb.css';
import '../../css/z/z9_d1p.css';
import '../../css/s/so-from-18.css';
import '../../css/t/tr-2c6-rw.css';
import '../../css/s/so-from-60.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c dza1eb"/><path class="a0m25c z9_d1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:loading-twotone-loop" {...props}></Icon>
