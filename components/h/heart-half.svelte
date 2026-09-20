<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/r/rmjj0t.css';
import '../../css/y/yqwu-f.css';
import '../../css/s/so-from-30.css';
import '../../css/s/so-from-16.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c rmjj0t"/><path class="a0m25c yqwu-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:heart-half" {...props}></Icon>
