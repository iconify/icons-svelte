<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a9a_esbwi.css';
import '../../css/s/sk-8-kkto.css';
import '../../css/w/we___fbjz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a9a_esbwi"/><path class="sk-8-kkto"/><path class="we___fbjz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:google-contacts-light" {...props}></Icon>
