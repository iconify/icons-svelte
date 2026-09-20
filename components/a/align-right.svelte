<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/p/pwt-kj.css';
import '../../css/c/cejmhd.css';
import '../../css/j/jx3bms.css';
import '../../css/b/bjzq0h.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c pwt-kj"/><path class="a0m25c cejmhd"/><path class="a0m25c jx3bms"/><path class="a0m25c bjzq0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:align-right" {...props}></Icon>
