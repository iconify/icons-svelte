<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/o/oq600w.css';
import '../../css/s/sdwher.css';
import '../../css/o/odxlyn.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c oq600w"/><path class="a0m25c sdwher"/><path class="a0m25c odxlyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:home-simple" {...props}></Icon>
