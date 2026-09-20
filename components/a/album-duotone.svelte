<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fchcg7aab.css';
import '../../css/b/bb6-6oplo.css';
import '../../css/a/af6c2lt3u.css';
import '../../css/q/qv1o886oj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="fchcg7aab"/><path class="bb6-6oplo"/><path class="af6c2lt3u"/><path class="qv1o886oj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:album-duotone" {...props}></Icon>
