<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/f/f5s6pk.css';
import '../../css/o/or6sls.css';
import '../../css/z/znhgjx.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c f5s6pk"/><path class="a0m25c or6sls"/><path class="a0m25c znhgjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:arrow-left-square" {...props}></Icon>
