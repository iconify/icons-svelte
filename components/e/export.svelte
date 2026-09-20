<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnlw47_jg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnlw47_jg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="typcn:export" {...props}></Icon>
