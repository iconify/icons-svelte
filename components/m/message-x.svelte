<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qwh3sic_y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qwh3sic_y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:message-x" {...props}></Icon>
