<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/w/wm005g.css';
import '../../css/o/okiwoc.css';
import '../../css/s/so-from-20.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c wm005g"/><path class="a0m25c okiwoc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:download-outline" {...props}></Icon>
