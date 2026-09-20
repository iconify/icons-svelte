<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/h/hdrl-z.css';
import '../../css/a/a97wxd.css';
import '../../css/p/p-0kvr.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c hdrl-z"/><path class="a0m25c a97wxd"/><circle class="p-0kvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:instagram" {...props}></Icon>
