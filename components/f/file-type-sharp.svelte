<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l0wd5e82z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l0wd5e82z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:file-type-sharp" {...props}></Icon>
