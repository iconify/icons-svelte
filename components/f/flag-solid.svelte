<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gwu5y9wqa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gwu5y9wqa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:flag-solid" {...props}></Icon>
