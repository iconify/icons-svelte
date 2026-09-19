<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sc7fzmsbi.css';
import '../../css/t/t4p58ib0k.css';
import '../../css/g/gv02961wk.css';
import '../../css/a/acfq-db-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="sc7fzmsbi"/><path class="t4p58ib0k"/><path class="gv02961wk"/><path class="acfq-db-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-crop" {...props}></Icon>
