<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mk3ez3bdw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mk3ez3bdw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:gog-com-logo-block" {...props}></Icon>
