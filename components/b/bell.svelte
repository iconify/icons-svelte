<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/x/x5ao8m.css';
import '../../css/w/w4pkou.css';
import '../../css/g/ge04hr.css';
import '../../css/s/so-from-4.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c x5ao8m"/><path class="a0m25c w4pkou"/><path class="a0m25c ge04hr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:bell" {...props}></Icon>
