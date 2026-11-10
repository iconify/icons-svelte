<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bw0nn2bxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bw0nn2bxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:calendar-arrow-path-solid" {...props}></Icon>
