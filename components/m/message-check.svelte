<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qtixo6etk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qtixo6etk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:message-check" {...props}></Icon>
