<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0zte_ban.css';
import '../../css/u/u_7efpbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a0zte_ban"/><path class="u_7efpbht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:creative-commons" {...props}></Icon>
