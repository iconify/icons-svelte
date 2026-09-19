<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iywjp2bkd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="iywjp2bkd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:admissions" {...props}></Icon>
