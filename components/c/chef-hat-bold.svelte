<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb-bq1nyz.css';
import '../../css/l/lofqyubof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb-bq1nyz"/><path class="lofqyubof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chef-hat-bold" {...props}></Icon>
