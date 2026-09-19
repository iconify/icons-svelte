<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u67vq-k0d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u67vq-k0d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:email-virus-filled" {...props}></Icon>
