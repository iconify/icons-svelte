<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf70tib7y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kf70tib7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h6-20-solid" {...props}></Icon>
