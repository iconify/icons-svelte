<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/v/vlsv6c.css';
import '../../css/l/lo--7m.css';
import '../../css/x/xx5a5k.css';
import '../../css/s/so-from-34.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c vlsv6c"/><path class="a0m25c lo--7m"/><path class="a0m25c xx5a5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:logout" {...props}></Icon>
