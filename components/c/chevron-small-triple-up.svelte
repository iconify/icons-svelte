<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/b/bxli5t.css';
import '../../css/l/ln52_i.css';
import '../../css/f/fm8ssf.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c bxli5t"/><path class="a0m25c ln52_i"/><path class="a0m25c fm8ssf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-small-triple-up" {...props}></Icon>
