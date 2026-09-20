<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uo5ov6bja.css';
import '../../css/w/wbz7ahcns.css';
import '../../css/l/lxerqacem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uo5ov6bja"/><path class="wbz7ahcns"/><path class="lxerqacem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:google-news" {...props}></Icon>
