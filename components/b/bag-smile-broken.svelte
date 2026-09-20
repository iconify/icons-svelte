<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/ouvmfj4ut.css';
import '../../css/b/bomz11bhc.css';
import '../../css/b/buo1kubox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ouvmfj4ut"/><path class="bomz11bhc"/><path class="buo1kubox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-smile-broken" {...props}></Icon>
