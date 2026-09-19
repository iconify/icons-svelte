<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ohifcbcwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ohifcbcwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:loyalty-card-barcode" {...props}></Icon>
