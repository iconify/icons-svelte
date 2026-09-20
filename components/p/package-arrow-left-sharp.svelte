<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6iqi4ruj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s6iqi4ruj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:package-arrow-left-sharp" {...props}></Icon>
