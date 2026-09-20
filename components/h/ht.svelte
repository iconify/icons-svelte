<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v_t11abfx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v_t11abfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:ht" {...props}></Icon>
