<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxner0b-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxner0b-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:acura" {...props}></Icon>
