<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvwxi7bhr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvwxi7bhr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:lock-open-solid" {...props}></Icon>
