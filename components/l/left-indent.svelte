<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gteaiobyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gteaiobyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:left-indent" {...props}></Icon>
