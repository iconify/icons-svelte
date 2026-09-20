<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bq0lnlb2z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-4,"top":-3};
const content = `<path class="bq0lnlb2z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:beer-f" {...props}></Icon>
