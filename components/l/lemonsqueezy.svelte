<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdq919bih.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cdq919bih"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:lemonsqueezy" {...props}></Icon>
