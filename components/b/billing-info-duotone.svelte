<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnsslsbew.css';
import '../../css/b/bog13w73d.css';
import '../../css/k/kila4w3tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnsslsbew"/><path class="bog13w73d"/><path class="kila4w3tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:billing-info-duotone" {...props}></Icon>
