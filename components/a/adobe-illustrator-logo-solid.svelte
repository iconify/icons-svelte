<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zjn48nb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zjn48nb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:adobe-illustrator-logo-solid" {...props}></Icon>
