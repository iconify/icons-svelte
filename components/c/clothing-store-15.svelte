<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol27jzu8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ol27jzu8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:clothing-store-15" {...props}></Icon>
