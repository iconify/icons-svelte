<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/na4d8xgib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="na4d8xgib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:aeromexico" {...props}></Icon>
