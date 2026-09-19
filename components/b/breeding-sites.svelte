<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq-0zhbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="bq-0zhbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:breeding-sites" {...props}></Icon>
