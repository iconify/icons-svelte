<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/k/kscc-z.css';
import '../../css/c/czadwe.css';
import '../../css/i/i--0rr.css';
import '../../css/s/so-from-60.css';
import '../../css/s/sw-cnj-zb.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c kscc-z"/><path class="a0m25c czadwe"/><path class="a0m25c i--0rr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:alert-loop" {...props}></Icon>
