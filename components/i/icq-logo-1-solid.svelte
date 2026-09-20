<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tk3gjkmip.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tk3gjkmip"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:icq-logo-1-solid" {...props}></Icon>
