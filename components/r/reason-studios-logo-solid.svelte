<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ex7dwfbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ex7dwfbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:reason-studios-logo-solid" {...props}></Icon>
