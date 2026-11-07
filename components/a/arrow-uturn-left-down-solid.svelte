<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibohz8bcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibohz8bcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:arrow-uturn-left-down-solid" {...props}></Icon>
