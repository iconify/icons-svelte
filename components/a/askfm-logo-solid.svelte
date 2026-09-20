<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds3z54bye.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ds3z54bye"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:askfm-logo-solid" {...props}></Icon>
