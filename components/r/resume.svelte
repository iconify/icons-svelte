<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l3958dbgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l3958dbgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:resume" {...props}></Icon>
