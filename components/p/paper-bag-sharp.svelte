<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af9nscbar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="af9nscbar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:paper-bag-sharp" {...props}></Icon>
