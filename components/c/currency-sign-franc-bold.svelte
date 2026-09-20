<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxcbiabyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cxcbiabyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:currency-sign-franc-bold" {...props}></Icon>
