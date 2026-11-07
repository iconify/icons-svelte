<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/apkqqc7pd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="apkqqc7pd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-right-down-20-solid" {...props}></Icon>
