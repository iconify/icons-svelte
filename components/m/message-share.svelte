<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eqdzjcbew.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eqdzjcbew"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-share" {...props}></Icon>
