<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/su_mzgvzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="su_mzgvzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-plump:industry-innovation-and-infrastructure-remix" {...props}></Icon>
