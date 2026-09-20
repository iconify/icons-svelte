<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9kl6cc3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="f9kl6cc3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:one-vesus-one-remix" {...props}></Icon>
