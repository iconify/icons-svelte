<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w37u6nj1g.css';
import '../../css/f/ft6yuqb7o.css';
import '../../css/l/l8fjmsy3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="w37u6nj1g"/><path class="ft6yuqb7o"/><path class="l8fjmsy3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:costa-rica" {...props}></Icon>
