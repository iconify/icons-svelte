<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i6omnp7lb.css';
import '../../css/i/i5h9yjk0d.css';
import '../../css/r/rb7oaobfl.css';
import '../../css/v/v783iab8c.css';
import '../../css/o/ob_nbubvj.css';
import '../../css/t/tr5qnfc9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="i6omnp7lb"/><path clip-rule="evenodd" class="i5h9yjk0d"/><path class="rb7oaobfl"/><circle class="v783iab8c"/><circle class="ob_nbubvj"/><circle class="tr5qnfc9g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:group-scan-fill" {...props}></Icon>
