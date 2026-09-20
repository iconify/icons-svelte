<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kz-wu_ira.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kz-wu_ira"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:link-remove-outline" {...props}></Icon>
