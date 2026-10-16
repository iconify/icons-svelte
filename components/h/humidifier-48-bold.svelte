<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlyw1hblf.css';
import '../../css/v/v4j2tfucd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nlyw1hblf"/><path class="v4j2tfucd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:humidifier-48-bold" {...props}></Icon>
