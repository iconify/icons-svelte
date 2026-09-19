<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hot97pbbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hot97pbbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:double-wall-switch" {...props}></Icon>
