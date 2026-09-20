<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgzblfb7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sgzblfb7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:dailybooth-logo-block" {...props}></Icon>
