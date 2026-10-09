<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/byr1kccnj.css';
import '../../css/v/v5yc14bmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="byr1kccnj"/><path class="v5yc14bmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:inbox-48" {...props}></Icon>
