<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/a/ain8nj.css';
import '../../css/x/x5jt8i.css';
import '../../css/g/g5y2dq.css';
import '../../css/s/so-from-62.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ain8nj"/><path class="a0m25c x5jt8i"/><path class="a0m25c g5y2dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:phone-add" {...props}></Icon>
