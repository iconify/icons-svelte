<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/begzp6bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-5};
const content = `<path class="begzp6bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:inbox-f" {...props}></Icon>
