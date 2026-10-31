<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuuyvdbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fuuyvdbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:pin-slash-solid" {...props}></Icon>
