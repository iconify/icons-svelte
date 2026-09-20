<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdpm5sixb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdpm5sixb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:expand-dashed-down-right-box-sharp" {...props}></Icon>
