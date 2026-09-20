<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/wocayubks.css';
import '../../css/a/a736vpyzo.css';
import '../../css/w/w13dkpbts.css';
import '../../css/y/yvq_4gmso.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<g class="cuyn6tgcc"><ellipse class="wocayubks"/><path class="a736vpyzo"/><ellipse class="w13dkpbts"/><path class="yvq_4gmso"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:myspace" {...props}></Icon>
