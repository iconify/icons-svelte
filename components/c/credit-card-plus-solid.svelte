<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2wt_3bzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a2wt_3bzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:credit-card-plus-solid" {...props}></Icon>
