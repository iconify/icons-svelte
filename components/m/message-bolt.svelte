<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eex20wb_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eex20wb_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:message-bolt" {...props}></Icon>
