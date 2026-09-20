<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h2pwz3vol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h2pwz3vol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:marina-bay-sand-fill" {...props}></Icon>
