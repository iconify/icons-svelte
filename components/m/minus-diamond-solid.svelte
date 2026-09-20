<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tcgbqwb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tcgbqwb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:minus-diamond-solid" {...props}></Icon>
