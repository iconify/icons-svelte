<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bt2-f3eym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bt2-f3eym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:basecamp-logo-1-block" {...props}></Icon>
