<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh3nhbj_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rh3nhbj_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:email-logo-block" {...props}></Icon>
