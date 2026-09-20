<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/h/haw7oj.css';
import '../../css/p/ppgzfw.css';
import '../../css/x/x5jt8i.css';
import '../../css/s/so-from-22.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c haw7oj"/><path class="a0m25c ppgzfw"/><path class="a0m25c x5jt8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:account-remove" {...props}></Icon>
