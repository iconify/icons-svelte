<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/b/bu0ohj.css';
import '../../css/l/l3-heb.css';
import '../../css/d/d-wzkz9p.css';
import '../../css/d/d-szjhyc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c bu0ohj"/><path class="a0m25c l3-heb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:close-to-menu-alt-transition" {...props}></Icon>
