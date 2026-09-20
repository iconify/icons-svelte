<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ta6jhe_wk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ta6jhe_wk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kik-logo-1-solid" {...props}></Icon>
