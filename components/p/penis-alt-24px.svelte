<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cydehgbyr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cydehgbyr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:penis-alt-24px" {...props}></Icon>
