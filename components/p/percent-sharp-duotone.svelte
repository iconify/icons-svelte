<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ko75q-b0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ko75q-b0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:percent-sharp-duotone" {...props}></Icon>
