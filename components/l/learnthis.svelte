<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c9vps2b8q.css';
import '../../css/i/i2nyp1b4x.css';
import '../../css/n/n3xsaaczl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":45,"height":45};
const content = `<path class="c9vps2b8q"/><path class="i2nyp1b4x"/><path class="n3xsaaczl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:learnthis" {...props}></Icon>
