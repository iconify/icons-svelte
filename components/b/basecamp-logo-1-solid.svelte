<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/im63o6nby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="im63o6nby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:basecamp-logo-1-solid" {...props}></Icon>
