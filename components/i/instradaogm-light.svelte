<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vyezo-ikf.css';
import '../../css/h/hw02_8bnp.css';
import '../../css/d/d978pz0hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vyezo-ikf"/><path class="hw02_8bnp"/><path class="d978pz0hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instradaogm-light" {...props}></Icon>
