<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4wsxaclo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e4wsxaclo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:banknote-x-sharp" {...props}></Icon>
