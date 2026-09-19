<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfa17oyjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="mfa17oyjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mountain" {...props}></Icon>
