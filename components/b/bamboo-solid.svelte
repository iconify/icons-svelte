<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihh9i5bby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ihh9i5bby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:bamboo-solid" {...props}></Icon>
