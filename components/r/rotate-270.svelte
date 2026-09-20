<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/k/k88ffy.css';
import '../../css/g/gs347e.css';
import '../../css/s/so-from-34.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c k88ffy"/><path class="a0m25c gs347e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:rotate-270" {...props}></Icon>
