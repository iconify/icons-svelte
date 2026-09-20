<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5h6soc8c.css';
import '../../css/n/n3kfhe2ac.css';
import '../../css/k/kpj5l1brl.css';
import '../../css/z/z2ozr-6hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c5h6soc8c"/><path class="n3kfhe2ac"/><path class="kpj5l1brl"/><path class="z2ozr-6hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:beets-flask" {...props}></Icon>
