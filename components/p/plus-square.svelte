<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/x/x8s03n.css';
import '../../css/u/ujphdc.css';
import '../../css/e/eaj3ug.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c x8s03n"/><path class="a0m25c ujphdc"/><path class="a0m25c eaj3ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:plus-square" {...props}></Icon>
