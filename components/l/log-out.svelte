<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/y/yo13rm.css';
import '../../css/w/w90myk.css';
import '../../css/v/vusf7y.css';
import '../../css/s/so-from-46.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c yo13rm"/><path class="a0m25c w90myk"/><path class="a0m25c vusf7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:log-out" {...props}></Icon>
