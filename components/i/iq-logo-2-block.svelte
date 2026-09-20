<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uodgz0val.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uodgz0val"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:iq-logo-2-block" {...props}></Icon>
