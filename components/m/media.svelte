<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ab3zrzlrq.css';
import '../../css/b/bldxs_3nx.css';
import '../../css/k/k5dgsrbqo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ab3zrzlrq"/><path class="bldxs_3nx"/><path class="k5dgsrbqo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:media" {...props}></Icon>
