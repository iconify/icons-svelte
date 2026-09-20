<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/u/uzg0oh.css';
import '../../css/n/nzn0tq.css';
import '../../css/s/so-from-10.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c uzg0oh"/><path class="a0m25c nzn0tq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:chevron-small-double-left" {...props}></Icon>
