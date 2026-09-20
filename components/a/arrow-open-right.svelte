<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/u/umd-9o.css';
import '../../css/c/crmxuy.css';
import '../../css/s/sbt7ak.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c umd-9o"/><path class="a0m25c crmxuy"/><path class="a0m25c sbt7ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-open-right" {...props}></Icon>
