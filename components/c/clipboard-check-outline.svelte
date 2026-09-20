<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh45oocjv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh45oocjv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:clipboard-check-outline" {...props}></Icon>
