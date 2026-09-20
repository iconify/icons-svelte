<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uf79mvbno.css';
import '../../css/n/nq01l99qg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="uf79mvbno"/><path clip-rule="evenodd" class="nq01l99qg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nextcloud-office-dark" {...props}></Icon>
