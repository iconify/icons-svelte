<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nus6ba.css';
import '../../css/j/jcq1ao.css';
import '../../css/a/a0m25c.css';
import '../../css/u/uu-53j.css';
import '../../css/z/zl4c-b.css';
import '../../css/b/botfzx.css';
import '../../css/d/d-4-9ugh.css';
import '../../css/d/d-n8ltvl.css';
import '../../css/s/so-from-32.css';
import '../../css/s/so-to-0.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGQjhHvebl"><path class="nus6ba"/><path class="jcq1ao"/></mask></defs><path class="a0m25c uu-53j"/><path class="a0m25c zl4c-b"/><path mask="url(#SVGQjhHvebl)" class="botfzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="line-md:buy-me-a-coffee" {...props}></Icon>
