<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yedj6il0o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yedj6il0o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-path-clock-solid" {...props}></Icon>
