<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liar723_x.css';
import '../../css/e/e85963y7t.css';
import '../../css/b/blqbp4b6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="liar723_x"/><path class="e85963y7t"/><path class="blqbp4b6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:email-mail-open-address" {...props}></Icon>
