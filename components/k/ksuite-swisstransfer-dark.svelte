<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhlkhxbii.css';
import '../../css/b/bp4av50wq.css';
import '../../css/s/soawemmgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhlkhxbii"/><path class="bp4av50wq"/><path class="soawemmgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ksuite-swisstransfer-dark" {...props}></Icon>
