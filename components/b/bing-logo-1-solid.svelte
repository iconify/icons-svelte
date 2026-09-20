<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uaqf9wbqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="uaqf9wbqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:bing-logo-1-solid" {...props}></Icon>
