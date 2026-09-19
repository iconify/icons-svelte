<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3f1cdmin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="s3f1cdmin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:megaphone2x-outline" {...props}></Icon>
