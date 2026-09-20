<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kzj-69x7k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kzj-69x7k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:image-fill" {...props}></Icon>
