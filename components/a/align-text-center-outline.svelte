<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8p4bpbrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n8p4bpbrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:align-text-center-outline" {...props}></Icon>
