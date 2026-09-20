<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/macbvkc0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-8,"top":-5};
const content = `<path class="macbvkc0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:chevron-left" {...props}></Icon>
