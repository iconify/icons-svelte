<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-rpmy.css';
import '../../css/a/a0m25c.css';
import '../../css/r/rmjj0t.css';
import '../../css/y/yqwu-f.css';
import '../../css/f/fill-to-0.css';
import '../../css/f/fill-to-0_3.css';
import '../../css/s/so-from-30.css';
import '../../css/s/so-from-16.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-rpmy"/><path class="a0m25c rmjj0t"/><path class="a0m25c yqwu-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:heart-half-twotone" {...props}></Icon>
