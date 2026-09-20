<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvm1ocb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fvm1ocb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:diigo-logo-1-solid" {...props}></Icon>
