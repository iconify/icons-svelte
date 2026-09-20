<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ox629tbsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ox629tbsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:flipboard-logo-block" {...props}></Icon>
