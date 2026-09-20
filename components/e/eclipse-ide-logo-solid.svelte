<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubo9a1bzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ubo9a1bzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:eclipse-ide-logo-solid" {...props}></Icon>
