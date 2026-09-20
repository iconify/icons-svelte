<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nkn6_o_df.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nkn6_o_df"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gift-card-line" {...props}></Icon>
