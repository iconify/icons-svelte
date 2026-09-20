<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6g_jcc6t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6g_jcc6t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:hair-dress-barber" {...props}></Icon>
