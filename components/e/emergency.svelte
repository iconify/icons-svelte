<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huotcacxk.css';
import '../../css/j/jixvyn1ey.css';
import '../../css/b/bs4b88r6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="huotcacxk"/><path class="jixvyn1ey"/><path class="bs4b88r6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:emergency" {...props}></Icon>
