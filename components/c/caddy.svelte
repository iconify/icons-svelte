<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jn30erbqx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jn30erbqx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:caddy" {...props}></Icon>
