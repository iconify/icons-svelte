<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqzkubchb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jqzkubchb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bnter-logo-block" {...props}></Icon>
