<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/k/kfcfzzxue.css';
import '../../css/d/dzlldxbzo.css';
import '../../css/z/zoixtkcpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="kfcfzzxue"/><path class="dzlldxbzo"/><path class="zoixtkcpw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mentoring" {...props}></Icon>
