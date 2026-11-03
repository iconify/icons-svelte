<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bd56e7efs.css';
import '../../css/g/gt5vq3bem.css';
import '../../css/k/kmzeb0bzh.css';
import '../../css/h/hfvqa-bro.css';
import '../../css/b/bicpjib-n.css';
import '../../css/e/ec78-xbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="bd56e7efs"/><path class="gt5vq3bem"/><path class="kmzeb0bzh"/><path class="hfvqa-bro"/><path class="bicpjib-n"/><path class="ec78-xbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:phpmyadmin-wordmark" {...props}></Icon>
