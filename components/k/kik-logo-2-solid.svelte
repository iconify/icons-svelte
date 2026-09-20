<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i00j8oboe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i00j8oboe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:kik-logo-2-solid" {...props}></Icon>
