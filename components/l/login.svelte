<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/k/khtx_s.css';
import '../../css/o/o6huwm.css';
import '../../css/v/v0wswn.css';
import '../../css/s/so-from-34.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c khtx_s"/><path class="a0m25c o6huwm"/><path class="a0m25c v0wswn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:login" {...props}></Icon>
