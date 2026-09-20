<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gh6d9rdxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gh6d9rdxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bugsnag-logo-solid" {...props}></Icon>
