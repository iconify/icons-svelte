<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/if0m9_emw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="if0m9_emw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:ello-logo-solid" {...props}></Icon>
