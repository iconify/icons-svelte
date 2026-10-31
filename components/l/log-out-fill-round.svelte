<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o55bhr6zy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o55bhr6zy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:log-out-fill-round" {...props}></Icon>
