<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/easitdb1p.css';
import '../../css/l/lndkxrb9v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="easitdb1p"/><path class="lndkxrb9v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:opensuse-wordmark" {...props}></Icon>
