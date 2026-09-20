<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aze2xou7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aze2xou7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:paytm" {...props}></Icon>
