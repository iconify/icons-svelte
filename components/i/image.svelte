<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fao72i.css';
import '../../css/q/qa-o7h.css';
import '../../css/i/i5u07d.css';
import '../../css/q/qxdeko.css';
import '../../css/s/so-from-66.css';
import '../../css/s/so-to-0.css';
import '../../css/f/fade-to-1.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fao72i qa-o7h"/><path class="i5u07d qa-o7h"/><circle class="qxdeko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:image" {...props}></Icon>
