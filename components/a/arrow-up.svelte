<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3nouv9br.css';
import '../../css/j/jcpgslicg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h3nouv9br"/><path class="jcpgslicg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontisto:arrow-up" {...props}></Icon>
