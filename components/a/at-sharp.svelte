<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/era_k9blm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="era_k9blm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:at-sharp" {...props}></Icon>
