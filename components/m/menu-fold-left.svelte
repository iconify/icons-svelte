<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0m25c.css';
import '../../css/n/nov9iu.css';
import '../../css/q/qqamjf.css';
import '../../css/s/suwabu.css';
import '../../css/k/k-a29e.css';
import '../../css/s/so-from-16.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c nov9iu"/><path class="a0m25c qqamjf"/><path class="a0m25c suwabu"/><path class="a0m25c k-a29e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:menu-fold-left" {...props}></Icon>
