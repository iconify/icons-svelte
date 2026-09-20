<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g44sicinw.css';
import '../../css/l/l3-5_c46r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g44sicinw"/><path clip-rule="evenodd" class="l3-5_c46r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:polyx" {...props}></Icon>
