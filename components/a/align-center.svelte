<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rt7-xmbvc.css';
import '../../css/m/m537j_bzb.css';
import '../../css/j/jh-_kon1i.css';
import '../../css/a/a235f6qsq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer rt7-xmbvc"/><path class="duoicon-primary-layer m537j_bzb"/><path class="duoicon-secondary-layer jh-_kon1i"/><path class="a235f6qsq duoicon-primary-layer"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="duo-icons:align-center" {...props}></Icon>
