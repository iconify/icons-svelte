<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn9mlm2hc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hn9mlm2hc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:minus" {...props}></Icon>
