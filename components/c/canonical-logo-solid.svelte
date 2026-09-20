<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wdlhyumbn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wdlhyumbn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:canonical-logo-solid" {...props}></Icon>
