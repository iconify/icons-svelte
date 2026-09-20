<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b67ohqy9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b67ohqy9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:check-circle-one-solid" {...props}></Icon>
